<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xef9d_vbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xef9d_vbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-west-square-fill" /></template>
