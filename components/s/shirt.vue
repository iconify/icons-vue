<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py9hl5bvu.css';
import '../../css/v/v6af_xb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py9hl5bvu"/><path class="v6af_xb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:shirt" /></template>
