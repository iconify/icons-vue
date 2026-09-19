<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvf88-v-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uvf88-v-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:trash2" /></template>
