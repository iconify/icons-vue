<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmt97czoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gmt97czoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-repo" /></template>
