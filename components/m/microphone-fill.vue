<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsz94vn-b.css';
import '../../css/k/kvf4_8b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsz94vn-b"/><path class="kvf4_8b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:microphone-fill" /></template>
