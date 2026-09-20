<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oob8d17yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oob8d17yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:salt-project" /></template>
