<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti-l6oboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti-l6oboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-sharp-fill" /></template>
