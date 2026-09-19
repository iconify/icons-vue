<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6m002bvn.css';
import '../../css/s/sgxi3fe_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="f6m002bvn"/><path class="sgxi3fe_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:search-fill-12" /></template>
