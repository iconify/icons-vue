<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_nxgx4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="v1_nxgx4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pray" /></template>
