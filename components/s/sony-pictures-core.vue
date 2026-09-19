<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3abcfb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3abcfb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sony-pictures-core" /></template>
