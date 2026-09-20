<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blo2lxb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blo2lxb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:the-spriters-resource" /></template>
