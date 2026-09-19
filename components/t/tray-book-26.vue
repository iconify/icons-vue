<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-8et3w6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="p-8et3w6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tray-book-26" /></template>
