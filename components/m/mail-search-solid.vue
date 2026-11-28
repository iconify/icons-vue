<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlh1tr96n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlh1tr96n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-search-solid" /></template>
