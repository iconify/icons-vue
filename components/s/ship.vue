<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbs0eacyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="hbs0eacyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ship" /></template>
