<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqt0-tbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eqt0-tbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:messenger-fill-16" /></template>
