<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<ellipse class="agh2s-srr"/><ellipse class="nrl430p0y"/><path class="k8eraccmu"/><path class="mpu-n6brm"/><path class="o6duxauby"/><path class="zixc60zag"/><g class="cgvivj-gr"><path class="ru5mv9ayt"/><circle class="bjdexjdod"/></g><circle class="df5ie_vqz"/><circle class="l_luvq_2m"/><circle class="g505b-36e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:old-woman-medium-light-skin-tone" /></template>
<style>
.agh2s-srr {
  cx: 32px;
  cy: 11.6px;
  fill: var(--svg-color--627a82, #627a82);
  rx: 15px;
  ry: 9.6px;
}

.bjdexjdod {
  cx: 19.7px;
  cy: 39.6px;
  r: 9px;
}

.cgvivj-gr {
  fill: var(--svg-color--454749, #454749);
}

.df5ie_vqz {
  cx: 19.7px;
  cy: 39.6px;
  r: 6px;
  fill: var(--svg-color--b4d7ee, #b4d7ee);
}

.g505b-36e {
  cx: 44.3px;
  cy: 39.6px;
  r: 6px;
  fill: var(--svg-color--b4d7ee, #b4d7ee);
}

.k8eraccmu {
  fill: var(--svg-color--fed0ac, #fed0ac);
  d: path("M57.3 28.9c-15.6-15.6-35.1-15.7-50.7 0l.1 17.3c0 7.5 7.4 15.8 25.7 15.8c17.3 0 24.9-6.8 24.9-15.8z");
}

.l_luvq_2m {
  cx: 44.3px;
  cy: 39.6px;
  r: 9px;
  fill: var(--svg-color--454749, #454749);
}

.mpu-n6brm {
  fill: var(--svg-color--454749, #454749);
  d: path("M39.2 51.7c.1.2.2.4.2.6c0 1.7-3.4 3.8-7.5 3.8s-7.5-2.1-7.5-3.8c0-.2.1-.5.2-.6c0 0 3.2 1.5 7.3 1.5s7.3-1.5 7.3-1.5");
}

.nrl430p0y {
  cx: 32px;
  cy: 15.6px;
  fill: var(--svg-color--c28fef, #c28fef);
  rx: 15px;
  ry: 9.6px;
}

.o6duxauby {
  fill: var(--svg-color--748a93, #748a93);
  d: path("M32 9.1c-29.5 0-35.8 23.7-25.2 32c0 0 5.2-8.8 16.1-13c28.4-10.9 20.5-19 9.1-19");
}

.ru5mv9ayt {
  d: path("M42.8 54.4c-.6 0-1.1-.2-1.6-.4s-1-.5-1.4-.9c-.8-.7-1.6-1.8-1.6-2.9l2.2 2.2c.8.6 1.6 1.2 2.4 2m-21.8 0c.8-.8 1.7-1.3 2.4-2c.8-.7 1.5-1.3 2.2-2.2c0 1.2-.7 2.2-1.6 2.9c-.4.4-.9.7-1.4.9c-.4.2-1 .4-1.6.4M17.7 41l-.3-3c.8-.1 1.9-.3 3.1-.5c5.9-1.1 15.7-3 26.4.6l-1 2.8c-9.9-3.4-19.2-1.6-24.8-.5c-1.3.3-2.5.5-3.4.6");
}

.zixc60zag {
  fill: var(--svg-color--8b9fa5, #8b9fa5);
  d: path("M32 9.1c-11.4 0-19.3 8.1 9.1 19c10.9 4.2 16.1 13 16.1 13c10.6-8.2 4.2-32-25.2-32");
}

</style>
