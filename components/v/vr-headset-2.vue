<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuym8zbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vuym8zbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:vr-headset-2" /></template>
