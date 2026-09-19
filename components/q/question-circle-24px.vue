<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go_uhwbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go_uhwbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:question-circle-24px" /></template>
