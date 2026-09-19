<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qap_r6b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qap_r6b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:stats-up-square-solid" /></template>
