<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdi1gtbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xdi1gtbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-anime-eye-and-eyebrow" /></template>
