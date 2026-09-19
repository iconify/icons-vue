<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_33i9b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_33i9b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-exclude-alt-filled" /></template>
