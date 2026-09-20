<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0c_hvufd.css';
import '../../css/h/h3q-mcb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="q0c_hvufd"/><path class="h3q-mcb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:save" /></template>
