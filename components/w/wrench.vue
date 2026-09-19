<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci1sux1or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ci1sux1or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:wrench" /></template>
