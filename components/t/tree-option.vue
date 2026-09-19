<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uijf33kfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uijf33kfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:tree-option" /></template>
