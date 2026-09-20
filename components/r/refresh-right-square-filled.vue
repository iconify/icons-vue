<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvmw99abz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvmw99abz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh-right-square-filled" /></template>
