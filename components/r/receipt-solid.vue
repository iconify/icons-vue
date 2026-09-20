<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6ksixvok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="p6ksixvok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:receipt-solid" /></template>
