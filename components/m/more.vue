<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpsvsbb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpsvsbb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:more" /></template>
