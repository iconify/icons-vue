<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htqu3gbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="htqu3gbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:tablet-landscape-fill" /></template>
