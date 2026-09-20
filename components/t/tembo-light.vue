<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asd640ooi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":153,"height":152};
const content = `<path clip-rule="evenodd" class="asd640ooi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tembo-light" /></template>
