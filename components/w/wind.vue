<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slaufquqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="slaufquqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:wind" /></template>
