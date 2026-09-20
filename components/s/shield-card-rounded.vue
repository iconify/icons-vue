<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhblkibvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-card-rounded" /></template>
<style>
.nhblkibvw {
  fill: currentColor;
  d: path("M13 21q-.69 0-1.153-.462t-.462-1.153V15q0-.69.462-1.153T13 13.385h7.385q.69 0 1.153.462T22 15v4.385q0 .69-.462 1.152T20.385 21zm0-1h7.385q.269 0 .442-.173t.173-.442v-2.193h-8.615v2.193q0 .269.173.442T13 20m-.615-3.808H21V15q0-.27-.173-.442q-.173-.173-.442-.173H13q-.27 0-.442.173q-.173.173-.173.442zM5 11.1V6.817q0-.51.295-.923t.755-.6l5.596-2.08q.162-.056.354-.056t.354.055l5.596 2.081q.46.187.755.6t.295.923v3.414q0 .31-.23.54t-.54.229H13q-1.708 0-2.854 1.146T9 15v3.21q.006.361-.31.508q-.315.147-.578-.105q-1.44-1.42-2.277-3.369Q5 13.296 5 11.1");
}

</style>
