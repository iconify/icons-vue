<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l--l7_zdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l--l7_zdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-warning-round" /></template>
