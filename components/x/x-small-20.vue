<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufby36brl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ufby36brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:x-small-20" /></template>
