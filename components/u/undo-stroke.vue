<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asve1nvpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asve1nvpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:undo-stroke" /></template>
