<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg_s3ib6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rg_s3ib6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:text-strikethrough" /></template>
