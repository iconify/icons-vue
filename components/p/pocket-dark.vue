<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjjjqcbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjjjqcbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pocket-dark" /></template>
