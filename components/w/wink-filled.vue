<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t46-pac6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t46-pac6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wink-filled" /></template>
