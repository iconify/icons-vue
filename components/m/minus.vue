<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqj8zfbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqj8zfbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minus" /></template>
