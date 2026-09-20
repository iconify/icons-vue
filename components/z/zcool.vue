<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q54_4lbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q54_4lbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zcool" /></template>
