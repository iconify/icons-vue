<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2p7kgczh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r2p7kgczh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:syringe" /></template>
