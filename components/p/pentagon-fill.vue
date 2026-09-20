<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhu87ubnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhu87ubnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pentagon-fill" /></template>
