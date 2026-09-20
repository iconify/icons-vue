<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_hxwwbci.css';
import '../../css/d/dpnipcczy.css';
import '../../css/k/k23eu_bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="h_hxwwbci"/><path class="dpnipcczy"/><path class="k23eu_bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:task-setting-filled" /></template>
