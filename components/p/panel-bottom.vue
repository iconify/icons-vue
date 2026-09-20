<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odwa7xv4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odwa7xv4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:panel-bottom" /></template>
