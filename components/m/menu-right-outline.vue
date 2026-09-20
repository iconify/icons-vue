<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asu8uubvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asu8uubvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:menu-right-outline" /></template>
