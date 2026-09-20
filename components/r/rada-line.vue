<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaqsa0buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaqsa0buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rada-line" /></template>
