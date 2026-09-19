<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egzvq3_2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="egzvq3_2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-remove-fill-16" /></template>
