<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqj_9dcii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="tqj_9dcii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:ok-circle" /></template>
