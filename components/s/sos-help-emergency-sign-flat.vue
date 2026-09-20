<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss-50dc0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ss-50dc0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:sos-help-emergency-sign-flat" /></template>
