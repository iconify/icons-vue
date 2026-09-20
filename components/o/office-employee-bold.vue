<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcjpb1kkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcjpb1kkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-employee-bold" /></template>
