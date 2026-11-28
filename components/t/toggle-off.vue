<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi99vslec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi99vslec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:toggle-off" /></template>
