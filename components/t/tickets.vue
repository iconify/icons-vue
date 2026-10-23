<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8w7kzs8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8w7kzs8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tickets" /></template>
