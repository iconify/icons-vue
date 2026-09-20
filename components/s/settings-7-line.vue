<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-d--rbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-d--rbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-7-line" /></template>
