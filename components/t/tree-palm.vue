<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n59p--but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n59p--but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tree-palm" /></template>
