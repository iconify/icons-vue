<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmzxt7bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hmzxt7bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:network-16" /></template>
