<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iko815bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iko815bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:thumbs-down" /></template>
