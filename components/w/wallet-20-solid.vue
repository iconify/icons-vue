<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exxj1ob2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="exxj1ob2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:wallet-20-solid" /></template>
