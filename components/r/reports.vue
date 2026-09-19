<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwbjh-b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwbjh-b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:reports" /></template>
