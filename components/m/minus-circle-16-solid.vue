<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt_aymnch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tt_aymnch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:minus-circle-16-solid" /></template>
