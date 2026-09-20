<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fber9ibwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fber9ibwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:pexels" /></template>
