<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmgpc8afi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jmgpc8afi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-send-email-message" /></template>
