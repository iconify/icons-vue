<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkjm_jbla.css';
import '../../css/b/bwibdw4bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkjm_jbla"/><path class="bwibdw4bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:no-entry" /></template>
