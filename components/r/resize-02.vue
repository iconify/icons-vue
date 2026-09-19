<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txl3pyamo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txl3pyamo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:resize-02" /></template>
