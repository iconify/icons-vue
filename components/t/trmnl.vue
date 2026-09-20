<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-oj7jbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-oj7jbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trmnl" /></template>
