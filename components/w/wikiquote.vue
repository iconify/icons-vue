<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-sbg5brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-sbg5brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wikiquote" /></template>
