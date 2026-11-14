<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv17p37qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv17p37qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-x" /></template>
