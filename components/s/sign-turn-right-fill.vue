<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2_u9j41c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f2_u9j41c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sign-turn-right-fill" /></template>
