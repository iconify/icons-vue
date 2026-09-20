<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9th1mpie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x9th1mpie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:percent-filled" /></template>
