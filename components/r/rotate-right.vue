<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4-pwgxub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4-pwgxub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rotate-right" /></template>
