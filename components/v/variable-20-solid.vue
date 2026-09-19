<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylwo9q-ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ylwo9q-ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:variable-20-solid" /></template>
