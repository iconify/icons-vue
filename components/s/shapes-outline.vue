<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9qvhrweo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shapes-outline" /></template>
<style>
.k9qvhrweo {
  fill: currentColor;
  d: path("m8.77 17.989l.224.008q.11.003.237.003q.148 0 .276-.003l.262-.008v1.165q0 .269.173.442t.442.173h8.77q.269 0 .442-.173t.173-.442v-8.77q0-.268-.173-.442q-.173-.173-.442-.173h-1.165l.008-.262Q18 9.379 18 9.23q0-.127-.003-.237l-.008-.225h1.165q.666 0 1.14.475t.475 1.14v8.77q0 .666-.474 1.14t-1.141.475h-8.77q-.666 0-1.14-.474t-.475-1.141zm-3.79-4.504q-1.75-1.745-1.75-4.25T4.977 4.98q1.746-1.75 4.251-1.75t4.255 1.746t1.749 4.251t-1.745 4.255t-4.251 1.749t-4.255-1.745m7.788-.718q1.463-1.462 1.463-3.537t-1.463-3.538t-3.537-1.462t-3.538 1.462t-1.462 3.538t1.462 3.537t3.538 1.463t3.537-1.463M9.231 9.231");
}

</style>
