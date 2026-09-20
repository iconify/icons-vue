<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rylgiac4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rylgiac4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:online-medical-call-service-solid" /></template>
