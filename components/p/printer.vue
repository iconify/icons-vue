<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgoq65bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgoq65bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:printer" /></template>
