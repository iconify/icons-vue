<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juntpgr-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juntpgr-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vip-crown-2-fill" /></template>
