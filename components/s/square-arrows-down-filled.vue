<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujl_nsbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ujl_nsbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrows-down-filled" /></template>
