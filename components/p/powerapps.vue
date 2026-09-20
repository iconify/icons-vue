<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4ctcbc3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4ctcbc3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:powerapps" /></template>
