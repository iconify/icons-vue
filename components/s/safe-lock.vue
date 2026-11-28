<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7a3z31yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7a3z31yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:safe-lock" /></template>
