<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h66-e1jim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h66-e1jim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt5-filled" /></template>
