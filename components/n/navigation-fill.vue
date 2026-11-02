<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xef50zl1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xef50zl1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:navigation-fill" /></template>
