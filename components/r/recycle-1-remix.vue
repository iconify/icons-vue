<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggo260boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ggo260boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:recycle-1-remix" /></template>
