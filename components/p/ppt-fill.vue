<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb9-z7owi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb9-z7owi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ppt-fill" /></template>
