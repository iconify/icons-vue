<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6yx8db9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6yx8db9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:moon" /></template>
