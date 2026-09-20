<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhhhj_z0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vhhhj_z0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-up" /></template>
