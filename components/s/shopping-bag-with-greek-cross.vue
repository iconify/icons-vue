<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kka7akb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kka7akb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-greek-cross" /></template>
