<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7un7q-3o.css';
import '../../css/p/p8sne4bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7un7q-3o"/><path clip-rule="evenodd" class="p8sne4bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ncr" /></template>
