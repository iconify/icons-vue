<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0s_31-tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z0s_31-tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:peace-fill" /></template>
