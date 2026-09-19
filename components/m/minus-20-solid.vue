<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv40vmb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rv40vmb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:minus-20-solid" /></template>
