<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1vsfgbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1vsfgbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:minus-circle-fill" /></template>
