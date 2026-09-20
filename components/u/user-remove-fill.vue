<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi8xt8byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi8xt8byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-remove-fill" /></template>
