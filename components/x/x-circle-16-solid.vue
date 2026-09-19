<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxr2-_brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qxr2-_brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:x-circle-16-solid" /></template>
