<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu9kdvbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nu9kdvbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-annotation" /></template>
