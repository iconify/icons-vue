<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq0gmnb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq0gmnb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paintbrush-sharp-fill" /></template>
