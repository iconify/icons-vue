<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms1l_22xi.css';
import '../../css/i/ini9cjbwb.css';
import '../../css/v/vrrpkgb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms1l_22xi"/><path class="ini9cjbwb"/><path class="vrrpkgb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:monitor-transfer-1-bold" /></template>
