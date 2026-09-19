<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uukvtj_ct.css';
import '../../css/f/f0n46xbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uukvtj_ct"/><path class="f0n46xbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:square-check" /></template>
