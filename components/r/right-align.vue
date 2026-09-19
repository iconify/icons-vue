<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rem_-jbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="rem_-jbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:right-align" /></template>
