<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq8js-0ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="eq8js-0ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:v-expand" /></template>
