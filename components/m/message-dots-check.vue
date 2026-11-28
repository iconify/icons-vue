<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slzel_86f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slzel_86f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-dots-check" /></template>
