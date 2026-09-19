<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5c6rdboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5c6rdboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:plus" /></template>
