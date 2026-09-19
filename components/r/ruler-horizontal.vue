<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf5gj7b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="pf5gj7b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ruler-horizontal" /></template>
