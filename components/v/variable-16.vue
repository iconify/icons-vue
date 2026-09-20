<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hirnc1viw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hirnc1viw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:variable-16" /></template>
