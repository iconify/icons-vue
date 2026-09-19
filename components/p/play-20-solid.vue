<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prw1abc4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="prw1abc4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:play-20-solid" /></template>
