<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9-cefbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o9-cefbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sign-in-16" /></template>
