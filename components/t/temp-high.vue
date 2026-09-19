<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/res45y0_a.css';
import '../../css/b/b-cf_z2lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="res45y0_a"/><path class="b-cf_z2lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:temp-high" /></template>
