<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5c1yxb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5c1yxb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:more-vertical-solid" /></template>
