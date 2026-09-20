<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkmnhqb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkmnhqb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-justifyright" /></template>
