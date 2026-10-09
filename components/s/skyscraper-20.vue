<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1l3kib5h.css';
import '../../css/s/srysnc0xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f1l3kib5h"/><path class="srysnc0xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skyscraper-20" /></template>
