<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnni-et4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qnni-et4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:threat-phone-solid" /></template>
