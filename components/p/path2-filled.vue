<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o51_o-bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o51_o-bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:path2-filled" /></template>
