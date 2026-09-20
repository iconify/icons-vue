<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ski0eqc8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ski0eqc8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:semver" /></template>
