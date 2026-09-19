<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arrw2cc3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="arrw2cc3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:venus-double" /></template>
