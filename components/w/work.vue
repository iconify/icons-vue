<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj1d7bwxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wj1d7bwxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work" /></template>
