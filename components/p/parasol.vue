<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp2t3nbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp2t3nbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:parasol" /></template>
