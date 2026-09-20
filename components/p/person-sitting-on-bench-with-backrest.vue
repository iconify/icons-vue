<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do9d8sb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="do9d8sb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sitting-on-bench-with-backrest" /></template>
