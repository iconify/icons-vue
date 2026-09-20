<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiqiw5b2f.css';
import '../../css/w/wz4v0s-qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiqiw5b2f"/><path clip-rule="evenodd" class="wz4v0s-qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:remove-alarm-fill" /></template>
