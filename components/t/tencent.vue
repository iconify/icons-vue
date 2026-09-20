<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cotznbc0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cotznbc0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tencent" /></template>
