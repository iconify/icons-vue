<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlt_dbcss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlt_dbcss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-left-24" /></template>
