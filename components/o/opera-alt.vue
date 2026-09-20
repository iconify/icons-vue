<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvesc-9me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvesc-9me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:opera-alt" /></template>
