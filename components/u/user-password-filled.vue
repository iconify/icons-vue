<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy-o-cb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy-o-cb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-password-filled" /></template>
