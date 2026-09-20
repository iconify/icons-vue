<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plbydi12c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plbydi12c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paintbrush-filled" /></template>
