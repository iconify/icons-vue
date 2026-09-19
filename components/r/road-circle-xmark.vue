<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggrgy84wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ggrgy84wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:road-circle-xmark" /></template>
