<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk4cjeb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk4cjeb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:microdotblog" /></template>
