<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7svzrqsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x7svzrqsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sort-numeric-up" /></template>
