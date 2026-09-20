<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_i1byt2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r_i1byt2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:recycle-bin-2-remix" /></template>
