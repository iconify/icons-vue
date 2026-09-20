<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct3j1ul3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct3j1ul3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-2-outline" /></template>
