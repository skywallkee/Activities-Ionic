# Activities-Ionic
Ionic App for Mobile Course

- Display schedule (online + offline)
- Add/edit activity (online + offline)
- Authenticate user

Activity:
- id: number
- name: string
- start: date
- end: date
- repeating: boolean

ActivityPhoto:
- activity: Activity
- photo: image

ActivityLocation:
- x: int
- y: int
- z: int
