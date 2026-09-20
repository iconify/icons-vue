<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmz93sk0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmz93sk0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-minus-outline" /></template>
