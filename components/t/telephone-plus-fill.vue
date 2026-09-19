<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivagqpbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ivagqpbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:telephone-plus-fill" /></template>
