<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rptrf_b-m.css';
import '../../css/p/pghzzobog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rptrf_b-m"/><path class="pghzzobog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:we-chat" /></template>
