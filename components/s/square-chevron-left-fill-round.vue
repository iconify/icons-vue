<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goj2twb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="goj2twb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-left-fill-round" /></template>
