<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7wt4vh5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7wt4vh5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:switch-vertical" /></template>
