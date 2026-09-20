<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6r_v6ent"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:server-person-rounded" /></template>
<style>
.i6r_v6ent {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.788q.69 0 1.153.463t.462 1.153v14.769q0 .69-.462 1.153T17.404 21H16.07q-.46 0-.845-.242t-.603-.666l-.315-.63q-.077-.154-.231-.25t-.327-.096h-3.48q-.174 0-.328.095q-.154.097-.23.25l-.316.631q-.217.423-.603.666T7.948 21zm2.626-6.25h5.516q.225 0 .387-.162t.163-.388q0-1.05-1.048-1.442T12 12.366t-2.26.392T8.693 14.2q0 .225.163.388t.387.162m3.824-4.434q.434-.433.434-1.066t-.434-1.066Q12.633 7.75 12 7.75t-1.066.434T10.5 9.25t.434 1.066q.433.434 1.066.434t1.066-.434");
}

</style>
