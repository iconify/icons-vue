<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4-o6s7ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4-o6s7ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:thumb-down-fill" /></template>
