<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbk5hhczk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pbk5hhczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:text-font" /></template>
