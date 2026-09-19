<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a682nkbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a682nkbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:percent" /></template>
