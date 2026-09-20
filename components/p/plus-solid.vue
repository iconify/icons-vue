<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg6h5fb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg6h5fb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:plus-solid" /></template>
