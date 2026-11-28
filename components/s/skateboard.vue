<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va4ask2uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va4ask2uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:skateboard" /></template>
