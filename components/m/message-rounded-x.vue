<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3e-t01qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3e-t01qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-rounded-x" /></template>
