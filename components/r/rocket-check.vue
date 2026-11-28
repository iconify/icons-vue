<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbd9j875s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbd9j875s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:rocket-check" /></template>
