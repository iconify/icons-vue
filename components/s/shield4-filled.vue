<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qayy5okhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qayy5okhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield4-filled" /></template>
