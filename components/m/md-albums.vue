<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgi0i4ykh.css';
import '../../css/e/e1am0fiug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tgi0i4ykh"/><path class="e1am0fiug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-albums" /></template>
