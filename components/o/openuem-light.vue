<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h568fcbae.css';
import '../../css/x/x1ipfizhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="h568fcbae"/><path class="x1ipfizhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openuem-light" /></template>
