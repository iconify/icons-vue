<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egi5c0z2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egi5c0z2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:measurement-1-filled" /></template>
