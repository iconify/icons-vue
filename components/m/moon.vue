<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxc5fvbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxc5fvbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:moon" /></template>
