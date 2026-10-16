<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgqpnubmx.css';
import '../../css/e/e8k7b6bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bgqpnubmx"/><path class="e8k7b6bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opengym" /></template>
