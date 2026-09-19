<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-ingig5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-ingig5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sausages-filled" /></template>
