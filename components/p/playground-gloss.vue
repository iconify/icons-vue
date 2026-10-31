<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfkdasvwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfkdasvwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:playground-gloss" /></template>
