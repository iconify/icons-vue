<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwb7h4upf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pwb7h4upf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:scatterplot" /></template>
