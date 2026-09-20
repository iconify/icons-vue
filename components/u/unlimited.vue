<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxjc86b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxjc86b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:unlimited" /></template>
