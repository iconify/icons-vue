<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa_fzkb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oa_fzkb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:yarn" /></template>
