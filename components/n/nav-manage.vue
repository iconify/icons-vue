<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elu6mbbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="elu6mbbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-manage" /></template>
