<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otrev-0be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="otrev-0be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-bold-outline" /></template>
