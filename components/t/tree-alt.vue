<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o07g97xvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o07g97xvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tree-alt" /></template>
