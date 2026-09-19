<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv3hncc0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv3hncc0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:panels-top-left" /></template>
