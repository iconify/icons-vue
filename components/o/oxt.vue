<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxg--r65y.css';
import '../../css/a/acs4rfber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxg--r65y"/><path class="acs4rfber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:oxt" /></template>
