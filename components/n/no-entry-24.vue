<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7q23qb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7q23qb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:no-entry-24" /></template>
