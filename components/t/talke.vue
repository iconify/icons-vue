<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo5f_u6rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bo5f_u6rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:talke" /></template>
