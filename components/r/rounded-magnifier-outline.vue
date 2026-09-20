<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjmeokubd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kjmeokubd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-outline" /></template>
