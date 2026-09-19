<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftmk4idvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ftmk4idvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:text-indent" /></template>
