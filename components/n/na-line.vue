<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b41e93k-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b41e93k-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:na-line" /></template>
