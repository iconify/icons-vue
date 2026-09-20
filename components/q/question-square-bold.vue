<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sztb4eboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sztb4eboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-square-bold" /></template>
