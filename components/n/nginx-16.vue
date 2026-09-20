<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdzxziqai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kdzxziqai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:nginx-16" /></template>
