<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpc-7dbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpc-7dbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shape-cube" /></template>
