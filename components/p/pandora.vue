<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1vl4ab-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":488};
const content = `<path class="n1vl4ab-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pandora" /></template>
