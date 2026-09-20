<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvl1kv60i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvl1kv60i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:quote-right" /></template>
