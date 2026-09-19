<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnha371ox.css';
import '../../css/o/o6hj5abyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnha371ox"/><path class="o6hj5abyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-rotate-ccw-filled" /></template>
