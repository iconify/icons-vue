<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vubm-y1ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vubm-y1ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:picking-path-filled" /></template>
