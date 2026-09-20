<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkh4jrmwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pin-road-outline" /></template>
<style>
.dkh4jrmwc {
  fill: currentColor;
  d: path("M8.5 20v-2.866h1V20zm0-6.558v-2.865h1v2.865zm0-6.558V4h1v2.885zM2.635 20L4.962 4h1L3.616 20zm14.104-.063q-.117-.064-.181-.19l-.085-.19q-.49-1.013-1.363-1.74q-.874-.728-1.483-1.655q-.368-.535-.52-1.164q-.151-.629-.151-1.262q0-1.647 1.203-2.756t2.872-1.109q1.661 0 2.815 1.18T21 13.895q0 .61-.171 1.191t-.514 1.075q-.615.92-1.496 1.642q-.88.722-1.335 1.748l-.083.193q-.062.128-.176.192t-.241.064t-.245-.063m1.433-4.88q.501-.501.501-1.192q0-.69-.501-1.191q-.5-.501-1.191-.501q-.69 0-1.192.501t-.5 1.191t.5 1.192t1.192.5t1.191-.5m-5.399-6.051L12.039 4h.98l.631 4.348q-.25.16-.46.312t-.417.346");
}

</style>
