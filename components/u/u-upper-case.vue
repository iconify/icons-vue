<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trio7-bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":527,"height":754};
const content = `<path class="trio7-bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:u-upper-case" /></template>
