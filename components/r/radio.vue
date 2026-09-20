<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wex3ut39i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wex3ut39i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:radio" /></template>
