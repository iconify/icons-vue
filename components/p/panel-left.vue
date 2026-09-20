<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwebqzeog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwebqzeog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:panel-left" /></template>
