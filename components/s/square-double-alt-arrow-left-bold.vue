<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubuw5dbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ubuw5dbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-double-alt-arrow-left-bold" /></template>
