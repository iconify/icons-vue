<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxsr6dk8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxsr6dk8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-cancel-01" /></template>
