<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wosc8pb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wosc8pb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:verify-filled" /></template>
