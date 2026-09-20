<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v52svw6cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v52svw6cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-ellipse" /></template>
