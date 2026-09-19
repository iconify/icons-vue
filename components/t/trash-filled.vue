<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf9hsacdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vf9hsacdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:trash-filled" /></template>
