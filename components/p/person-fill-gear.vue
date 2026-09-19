<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv_eu50mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bv_eu50mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-fill-gear" /></template>
