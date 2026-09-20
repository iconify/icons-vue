<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etts-obta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="etts-obta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mosquito" /></template>
