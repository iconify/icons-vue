<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqzav-bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qqzav-bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pet-paw-remix" /></template>
