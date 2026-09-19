<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2bx2sphf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2bx2sphf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:oqee" /></template>
