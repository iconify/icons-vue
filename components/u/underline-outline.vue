<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ausc4-b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ausc4-b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:underline-outline" /></template>
