<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx1_a_bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rx1_a_bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:signal" /></template>
