<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elqvd6b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="elqvd6b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:printer" /></template>
