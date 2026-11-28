<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anu_i_-lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="anu_i_-lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-valve-beside-sewage-pipe-cross-section" /></template>
