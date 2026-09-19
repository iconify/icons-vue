<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbmw3_k5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cbmw3_k5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:phone-x-mark" /></template>
