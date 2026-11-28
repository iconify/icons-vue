<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf-4ykbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-4ykbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plug-zap-solid" /></template>
