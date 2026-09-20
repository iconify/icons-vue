<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1b1yz-3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w1b1yz-3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:plus" /></template>
