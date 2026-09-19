<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf4fpbcob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cf4fpbcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:text-line-height" /></template>
