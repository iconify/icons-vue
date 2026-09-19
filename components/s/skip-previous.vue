<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr7fh5uak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr7fh5uak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:skip-previous" /></template>
