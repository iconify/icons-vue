<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvw8lnbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nvw8lnbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:syringe" /></template>
