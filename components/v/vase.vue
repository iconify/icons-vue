<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhfnh-n6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vhfnh-n6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vase" /></template>
