<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcn9u5-6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcn9u5-6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mingcute-fill" /></template>
