<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb2axfb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gb2axfb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rewind" /></template>
