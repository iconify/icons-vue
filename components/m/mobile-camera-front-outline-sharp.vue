<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq5p82jwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-camera-front-outline-sharp" /></template>
<style>
.qq5p82jwn {
  fill: currentColor;
  d: path("m10.35 21.808l-.708-.708l1.6-1.6H6v-1h5.242l-1.6-1.6l.708-.708L13.158 19zM7 13.688q1.123-.517 2.472-.833q1.35-.317 2.528-.317t2.528.317t2.472.833V4H7zm7 5.812v-1h4v1zm-3.77-9.267q-.73-.729-.73-1.77t.729-1.77t1.769-.731t1.771.728t.731 1.77t-.728 1.77t-1.77.732t-1.771-.729m2.828-.713q.441-.441.441-1.059t-.441-1.058q-.442-.442-1.059-.442t-1.059.442t-.441 1.058t.441 1.06q.442.44 1.059.44t1.059-.44M6 17V3h12v4.83h.923v3.686H18V17h-1v-2.165q-.942-.572-2.34-.934T12 13.538t-2.66.363t-2.34.934V17z");
}

</style>
