<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ipmcpfbtp"/><path class="d5ftuabrz"/><path class="e27i13xvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:three-speech-bubbles" /></template>
<style>
.d5ftuabrz {
  fill: var(--svg-color--e580ae, #e580ae);
  d: path("M29.867 31.934c-11.244 0-20.362 6.099-20.362 13.618c0 4.218 2.869 7.987 7.369 10.484c-.556 1.836-2.152 4.142-6.198 6.312c0 0-1.17.786 0 1.749c0 0 7.825.462 13.386-5.492c1.839.366 3.785.566 5.806.566c11.242 0 20.357-6.099 20.357-13.617c0-7.522-9.116-13.62-20.358-13.62");
}

.e27i13xvu {
  fill: var(--svg-color--74c5ed, #74c5ed);
  d: path("M20.361-.238C9.116-.238 0 5.858 0 13.379c0 4.218 2.869 7.986 7.369 10.483c-.556 1.836-2.152 4.141-6.199 6.312c0 0-1.169.787 0 1.75c0 0 7.826.462 13.387-5.493a30 30 0 0 0 5.805.566c11.242 0 20.357-6.098 20.357-13.618C40.718 5.858 31.603-.238 20.361-.238");
}

.ipmcpfbtp {
  fill: var(--svg-color--bcbec0, #bcbec0);
  d: path("M23.21 26.319c0 7.52 9.115 13.618 20.357 13.618c2.02 0 3.966-.2 5.806-.566c5.561 5.956 13.386 5.494 13.386 5.494c1.17-.963 0-1.752 0-1.752c-4.047-2.171-5.643-4.476-6.198-6.311c4.499-2.497 7.368-6.267 7.368-10.484c0-7.521-9.117-13.618-20.361-13.618S23.21 18.796 23.21 26.319");
}

</style>
