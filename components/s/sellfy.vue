<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wusv9qnpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wusv9qnpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sellfy" /></template>
