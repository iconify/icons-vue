<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccdihcchd.css';
import '../../css/n/nxxqhr_ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccdihcchd"/><path class="nxxqhr_ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:star" /></template>
