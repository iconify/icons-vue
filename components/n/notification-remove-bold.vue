<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr2f8pbje.css';
import '../../css/x/xjq0yvb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr2f8pbje"/><path class="xjq0yvb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notification-remove-bold" /></template>
