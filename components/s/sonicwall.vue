<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcvcl704v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcvcl704v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sonicwall" /></template>
