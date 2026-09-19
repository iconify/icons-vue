<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laalgyble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laalgyble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:torus-filled" /></template>
