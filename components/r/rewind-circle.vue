<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myv0d9bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myv0d9bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:rewind-circle" /></template>
