<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfh65chdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yfh65chdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:png" /></template>
