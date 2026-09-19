<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0w1s3bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0w1s3bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:puzzle-piece" /></template>
