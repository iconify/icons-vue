<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdr7lkbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdr7lkbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:songoda" /></template>
