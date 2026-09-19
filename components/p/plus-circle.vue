<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e78vbih2x.css';
import '../../css/b/bwibdw4bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e78vbih2x"/><path class="bwibdw4bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plus-circle" /></template>
