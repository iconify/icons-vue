<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytr8o7b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytr8o7b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-check-sharp" /></template>
