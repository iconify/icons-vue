<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaz5m1bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaz5m1bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:quote-right" /></template>
