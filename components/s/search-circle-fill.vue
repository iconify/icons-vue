<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxp2azrgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rxp2azrgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:search-circle-fill" /></template>
