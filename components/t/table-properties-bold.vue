<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5-2keb6j"/><path class="ngqtlcoaq"/><path class="hqo5-g8_n"/><path class="w2qhwh4_j"/><path class="uez9mdbud"/><path class="ox_n4815v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-properties-bold" /></template>
<style>
.g5-2keb6j {
  fill: currentColor;
  d: path("M14.25 16.0828V21.9978C13.858 21.9997 13.4419 21.9998 13 21.9998H11C7.22917 21.9998 5.34348 22.0001 4.17188 20.8289C3.23934 19.8963 3.05152 18.5109 3.0127 16.0828H14.25Z");
}

.hqo5-g8_n {
  fill: currentColor;
  d: path("M21 9.99976V13.9998C21 14.1992 20.9992 14.3937 20.999 14.5828H15.75V9.41675H20.999C20.9992 9.60592 21 9.8002 21 9.99976Z");
}

.ngqtlcoaq {
  fill: currentColor;
  d: path("M20.9873 16.0828C20.9485 18.5109 20.7607 19.8963 19.8281 20.8289C18.9846 21.6721 17.7708 21.9063 15.75 21.9724V16.0828H20.9873Z");
}

.ox_n4815v {
  fill: currentColor;
  d: path("M14.25 2.00171V7.91675H3.0127C3.05153 5.48888 3.2394 4.10411 4.17188 3.17163C5.34346 2.00017 7.22888 1.99976 11 1.99976H13C13.4419 1.99976 13.858 1.99982 14.25 2.00171Z");
}

.uez9mdbud {
  fill: currentColor;
  d: path("M15.75 2.02612C17.7711 2.09225 18.9846 2.32818 19.8281 3.17163C20.7606 4.10411 20.9485 5.48888 20.9873 7.91675H15.75V2.02612Z");
}

.w2qhwh4_j {
  fill: currentColor;
  d: path("M14.25 9.41675V14.5828H3.00098C3.0008 14.3937 3 14.1992 3 13.9998V9.99976C3 9.8002 3.0008 9.60592 3.00098 9.41675H14.25Z");
}

</style>
