<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzo2qob1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzo2qob1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tanstack" /></template>
