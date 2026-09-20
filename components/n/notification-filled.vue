<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv1mz-i2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv1mz-i2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:notification-filled" /></template>
