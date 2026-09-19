<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-33dl0tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x-33dl0tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:starburst-solid" /></template>
