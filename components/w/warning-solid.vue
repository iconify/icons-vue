<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbhdrnbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tbhdrnbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:warning-solid" /></template>
