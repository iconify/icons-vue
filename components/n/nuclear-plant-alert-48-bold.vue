<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi1_s4oue.css';
import '../../css/a/a-1g_ibpd.css';
import '../../css/y/ygtv74bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vi1_s4oue"/><path class="a-1g_ibpd"/><path class="ygtv74bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-alert-48-bold" /></template>
