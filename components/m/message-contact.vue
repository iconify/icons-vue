<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut95bbxop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:message-contact" /></template>
<style>
.ut95bbxop {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25h13.5q1.346 0 2.298.952T21.75 5.5v10q0 1.346-.952 2.298t-2.298.952h-1.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T17.5 18q0-5.75-4.75-5.75T8 18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T9.5 18q0-4.25 3.25-4.25T16 18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H9L5.2 21.6q-.059.044-.126.076q-.066.032-.138.051q-.071.018-.145.022t-.147-.007t-.143-.034q-.07-.025-.133-.063q-.064-.037-.119-.087t-.099-.108q-.073-.097-.112-.213Q4 21.122 4 21v-2.342q-2.25-.454-2.25-3.158v-10q0-1.346.952-2.298T5 2.25M15.75 8q0-3-3-3t-3 3t3 3t3-3");
}

</style>
