<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwkj2k1fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zwkj2k1fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:pet-animals-cat" /></template>
