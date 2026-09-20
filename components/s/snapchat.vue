<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylwx14bgz.css';
import '../../css/w/w3xbe3b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylwx14bgz"/><path class="w3xbe3b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:snapchat" /></template>
