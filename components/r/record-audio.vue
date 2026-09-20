<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwuatl62v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwuatl62v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:record-audio" /></template>
