<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myk9ll1ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myk9ll1ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:parking-solid" /></template>
