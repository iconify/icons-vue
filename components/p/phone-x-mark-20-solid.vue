<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgxfs0w7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hgxfs0w7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:phone-x-mark-20-solid" /></template>
