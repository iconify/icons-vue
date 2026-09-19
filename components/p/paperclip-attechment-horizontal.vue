<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbg421biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbg421biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:paperclip-attechment-horizontal" /></template>
