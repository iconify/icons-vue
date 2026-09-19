<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd4f_sbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd4f_sbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:radical" /></template>
