<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efqq9-b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efqq9-b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mic-off-filled" /></template>
