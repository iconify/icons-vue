<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d87_fsf7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d87_fsf7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-follow-fill" /></template>
