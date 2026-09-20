<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwpfp-bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dwpfp-bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:test-16" /></template>
