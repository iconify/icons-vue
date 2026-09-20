<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu4u9_s1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu4u9_s1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:papermc" /></template>
