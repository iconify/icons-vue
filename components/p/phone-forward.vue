<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhh5x7blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rhh5x7blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-forward" /></template>
