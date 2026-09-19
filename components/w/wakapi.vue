<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayy9uee8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayy9uee8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wakapi" /></template>
