<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmcspk2nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hmcspk2nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-justify" /></template>
