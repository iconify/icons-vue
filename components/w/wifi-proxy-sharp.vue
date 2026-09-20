<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v50fqx7uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wifi-proxy-sharp" /></template>
<style>
.v50fqx7uh {
  fill: currentColor;
  d: path("M12 21L0 9q2.375-2.425 5.488-3.713T12 4t6.513 1.288T24 9l-2.475 2.475q-.575-.275-1.213-.413t-1.287-.137q-2.525 0-4.3 1.775T12.95 17q0 .65.138 1.288T13.5 19.5zm4 0v-7h4.25v2.75H23V21zm1.5-4.25h1.25V15.5H17.5zm0 2.75h1.25v-1.25H17.5zm2.75 0h1.25v-1.25h-1.25z");
}

</style>
