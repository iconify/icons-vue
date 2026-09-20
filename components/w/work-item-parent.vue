<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emsxux5lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="emsxux5lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work-item-parent" /></template>
