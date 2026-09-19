<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt86yobog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kt86yobog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:nodejs" /></template>
