<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_jv0gbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_jv0gbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:paint-bucket" /></template>
