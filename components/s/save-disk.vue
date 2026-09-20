<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppaggub0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ppaggub0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:save-disk" /></template>
