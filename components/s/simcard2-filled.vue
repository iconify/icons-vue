<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkybv0bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkybv0bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:simcard2-filled" /></template>
