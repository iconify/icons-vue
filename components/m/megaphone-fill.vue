<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6hb5pd3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x6hb5pd3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:megaphone-fill" /></template>
