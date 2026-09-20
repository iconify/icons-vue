<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrqtygbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrqtygbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-setting-filled" /></template>
