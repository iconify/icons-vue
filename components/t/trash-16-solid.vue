<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tncv02bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tncv02bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:trash-16-solid" /></template>
