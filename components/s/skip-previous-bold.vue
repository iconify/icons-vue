<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kerg8qktr.css';
import '../../css/w/wjmxqyb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kerg8qktr"/><path class="wjmxqyb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skip-previous-bold" /></template>
