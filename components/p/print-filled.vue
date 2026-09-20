<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igsf73ies.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="igsf73ies"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:print-filled" /></template>
