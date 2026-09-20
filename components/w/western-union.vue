<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlix1cbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlix1cbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:western-union" /></template>
