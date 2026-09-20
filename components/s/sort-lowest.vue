<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s11-_tb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s11-_tb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:sort-lowest" /></template>
