<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezp-wvbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ezp-wvbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pubky" /></template>
