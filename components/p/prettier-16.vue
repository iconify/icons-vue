<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkpun9bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kkpun9bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:prettier-16" /></template>
