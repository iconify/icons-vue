<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyg-96bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eyg-96bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pin-16-solid" /></template>
