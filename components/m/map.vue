<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwttfvnkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="xwttfvnkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:map" /></template>
