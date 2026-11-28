<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptk6-3vvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptk6-3vvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tag-x" /></template>
