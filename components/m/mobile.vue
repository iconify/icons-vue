<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guv2ysbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="guv2ysbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:mobile" /></template>
