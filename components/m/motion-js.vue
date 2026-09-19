<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu1jccmbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b uu1jccmbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:motion-js" /></template>
