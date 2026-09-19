<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrbwxrw4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrbwxrw4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:swatch" /></template>
