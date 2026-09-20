<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3dnj8n0d.css';
import '../../css/z/zsrd_jbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3dnj8n0d"/><path class="zsrd_jbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mbl" /></template>
