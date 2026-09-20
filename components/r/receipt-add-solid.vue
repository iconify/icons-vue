<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atxjksknp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="atxjksknp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:receipt-add-solid" /></template>
