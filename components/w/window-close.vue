<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gks8du_si.css';
import '../../css/s/sceipoxjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gks8du_si"/><path class="sceipoxjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:window-close" /></template>
