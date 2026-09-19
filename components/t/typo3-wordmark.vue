<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1n-b7bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k1n-b7bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:typo3-wordmark" /></template>
