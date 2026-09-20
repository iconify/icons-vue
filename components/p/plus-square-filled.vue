<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ociw6s2sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ociw6s2sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plus-square-filled" /></template>
