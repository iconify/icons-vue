<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnylftb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dnylftb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-send-reply-all-solid" /></template>
