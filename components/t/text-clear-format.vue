<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iihkrub1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iihkrub1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:text-clear-format" /></template>
