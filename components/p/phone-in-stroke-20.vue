<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d213agn5f.css';
import '../../css/g/gedrdccde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d213agn5f"/><path class="gedrdccde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-in-stroke-20" /></template>
