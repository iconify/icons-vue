<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik1pfo3tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik1pfo3tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:peer-to-peer-02" /></template>
