<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_oen7vak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u_oen7vak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:polka-dot-circle-solid" /></template>
