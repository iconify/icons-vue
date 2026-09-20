<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaac9aczt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qaac9aczt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-left-up-outline" /></template>
