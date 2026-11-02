<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk3737bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk3737bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:t-shirt-line" /></template>
