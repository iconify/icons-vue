<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njrjhmbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="njrjhmbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shield-slash-fill" /></template>
