<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-iyy091g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-iyy091g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti-cam-flex" /></template>
