<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lod1keb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lod1keb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rake-line" /></template>
