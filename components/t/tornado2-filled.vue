<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2jqw9bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2jqw9bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tornado2-filled" /></template>
