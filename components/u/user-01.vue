<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-45xac-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-45xac-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:user-01" /></template>
