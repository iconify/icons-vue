<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bli81z1tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bli81z1tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:weibo-line" /></template>
