<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmd0t1b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmd0t1b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:styleshare" /></template>
