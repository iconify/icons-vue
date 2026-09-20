<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzzapp00n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzzapp00n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:oil-line" /></template>
