<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anw-b9pqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="anw-b9pqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-top-right-and-minus" /></template>
