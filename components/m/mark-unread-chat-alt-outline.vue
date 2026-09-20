<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u48lxlbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-unread-chat-alt-outline" /></template>
<style>
.u48lxlbnx {
  fill: currentColor;
  d: path("M6.5 13.5h7v-1h-7zm0-3h11v-1h-11zm0-3h9.942v-.023q-.367-.18-.639-.418t-.495-.559H6.5zM3 20.077V4.616q0-.691.463-1.153T4.615 3H14.6q-.061.25-.071.49t-.006.51H4.616q-.231 0-.424.192T4 4.615v13.03L5.65 16h13.735q.23 0 .423-.192t.192-.423V8.342q.287-.067.527-.155q.24-.087.473-.225v7.423q0 .69-.462 1.153T19.385 17H6.077zM4 4.616v12.769V4zM17.23 5.73Q16.5 5 16.5 3.96t.73-1.769t1.77-.73t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73");
}

</style>
