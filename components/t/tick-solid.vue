<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvjnoq-4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="zvjnoq-4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:tick-solid" /></template>
