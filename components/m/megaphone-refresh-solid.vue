<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiylwmb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qiylwmb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:megaphone-refresh-solid" /></template>
