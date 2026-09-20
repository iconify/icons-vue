<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahp9sifuv.css';
import '../../css/f/f8g2gccrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahp9sifuv"/><path class="f8g2gccrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-setting-filled" /></template>
