<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o84wmlb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o84wmlb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tablet-solid" /></template>
