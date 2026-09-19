<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2x2vzbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b2x2vzbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-stroke-16" /></template>
