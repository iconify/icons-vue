<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfwc7mqrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfwc7mqrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-dashed-sharp" /></template>
