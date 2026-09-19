<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_mdmmqat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="o_mdmmqat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:searchdocument" /></template>
