<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkom-ab6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkom-ab6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mulesoft" /></template>
