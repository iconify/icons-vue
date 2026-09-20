<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt42c3erm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt42c3erm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:plus" /></template>
