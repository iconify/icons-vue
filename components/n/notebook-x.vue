<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aidyh2m1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aidyh2m1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:notebook-x" /></template>
