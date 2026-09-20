<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua3jl-yvs.css';
import '../../css/q/q3ohsnbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ua3jl-yvs"/><path clip-rule="evenodd" class="q3ohsnbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:user-portrayal-filled" /></template>
