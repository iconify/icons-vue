<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3n4852oq.css';
import '../../css/o/onfml7bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k3n4852oq"/><path class="onfml7bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:volume" /></template>
