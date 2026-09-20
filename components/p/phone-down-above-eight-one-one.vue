<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-1uf6h2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t-1uf6h2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-eight-one-one" /></template>
