<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcv8-5svs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bcv8-5svs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:umbrella" /></template>
