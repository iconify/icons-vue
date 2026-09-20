<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neklxg2vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="neklxg2vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:peertube-16" /></template>
