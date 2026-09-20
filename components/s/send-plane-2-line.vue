<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6kfzrspk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6kfzrspk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:send-plane-2-line" /></template>
