<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyrurpboo.css';
import '../../css/w/whmprw8rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dyrurpboo"/><path class="whmprw8rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-heart-48" /></template>
