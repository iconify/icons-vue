<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s72_n9bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s72_n9bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:phone" /></template>
