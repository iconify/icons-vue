<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjj48ibfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bjj48ibfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:plug-filled" /></template>
