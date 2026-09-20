<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdhskebrq.css';
import '../../css/l/l51b0lbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdhskebrq"/><path class="l51b0lbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mobile-shortcut-filled" /></template>
