<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpeh4lb3t.css';
import '../../css/n/nyxp3bb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="fpeh4lb3t"/><path class="nyxp3bb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:number" /></template>
