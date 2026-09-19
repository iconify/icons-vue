<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rejyhqb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rejyhqb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:synchronize-fill" /></template>
