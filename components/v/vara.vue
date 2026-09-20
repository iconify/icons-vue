<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3ms8cnax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a3ms8cnax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vara" /></template>
