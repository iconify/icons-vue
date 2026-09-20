<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv1zt7bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hv1zt7bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:new-badge-highlight-remix" /></template>
