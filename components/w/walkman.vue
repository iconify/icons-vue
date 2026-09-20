<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g85bdcbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g85bdcbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:walkman" /></template>
