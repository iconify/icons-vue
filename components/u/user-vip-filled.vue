<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg9q6gb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9q6gb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-vip-filled" /></template>
