<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvf8mrwdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvf8mrwdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:vuejs" /></template>
