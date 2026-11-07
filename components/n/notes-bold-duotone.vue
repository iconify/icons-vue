<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw3wxe0oi.css';
import '../../css/f/fnwhem6it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nw3wxe0oi"/><path class="fnwhem6it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notes-bold-duotone" /></template>
