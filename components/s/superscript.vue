<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eavb5gb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eavb5gb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:superscript" /></template>
