<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3_4s2eta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q3_4s2eta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:usb-type-c" /></template>
