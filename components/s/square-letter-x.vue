<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvih1op7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvih1op7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-x" /></template>
