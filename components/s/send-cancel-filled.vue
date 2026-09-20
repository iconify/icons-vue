<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihvmary2y.css';
import '../../css/y/y1oz-jo5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihvmary2y"/><path class="y1oz-jo5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:send-cancel-filled" /></template>
