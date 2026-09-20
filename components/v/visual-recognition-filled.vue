<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfwmerbfq.css';
import '../../css/z/zbqhemi-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfwmerbfq"/><path class="zbqhemi-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:visual-recognition-filled" /></template>
