<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhlafpbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dhlafpbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:square-brackets" /></template>
