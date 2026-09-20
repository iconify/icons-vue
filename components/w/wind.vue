<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb0jcv6dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb0jcv6dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:wind" /></template>
