<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfs6bob9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfs6bob9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:virustotal-logo-block" /></template>
