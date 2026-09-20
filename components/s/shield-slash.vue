<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5lgu_8hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5lgu_8hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield-slash" /></template>
