<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2_0khbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2_0khbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:store" /></template>
