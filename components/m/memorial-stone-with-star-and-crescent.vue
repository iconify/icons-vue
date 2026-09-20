<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr02q8bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tr02q8bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-star-and-crescent" /></template>
