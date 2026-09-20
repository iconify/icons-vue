<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2ucr5b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2ucr5b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-direction-right-fill" /></template>
