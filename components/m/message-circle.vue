<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t222qp1dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t222qp1dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:message-circle" /></template>
