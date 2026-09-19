<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-dfw8bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l-dfw8bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:tsunami" /></template>
