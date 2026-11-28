<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atm5b0wqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="atm5b0wqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:whistle-bold" /></template>
