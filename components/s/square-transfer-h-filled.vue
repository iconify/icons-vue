<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt-s9mb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dt-s9mb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-transfer-h-filled" /></template>
