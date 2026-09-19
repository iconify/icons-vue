<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbwga7b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pbwga7b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shopping-bag-16-solid" /></template>
