<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5n_-8btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="v5n_-8btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:shopping-bag" /></template>
