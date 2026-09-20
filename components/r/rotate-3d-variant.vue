<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgqkpwb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgqkpwb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rotate-3d-variant" /></template>
