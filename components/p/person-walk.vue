<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdvcg_qid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pdvcg_qid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:person-walk" /></template>
