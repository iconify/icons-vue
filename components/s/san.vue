<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvcu7mk6y.css';
import '../../css/z/zzqt9rbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvcu7mk6y"/><path clip-rule="evenodd" class="zzqt9rbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:san" /></template>
