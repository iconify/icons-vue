<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks_7h928z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ks_7h928z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:wrench-16-solid" /></template>
