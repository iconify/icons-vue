<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waj_2hban.css';
import '../../css/z/z4hja-bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waj_2hban"/><path class="z4hja-bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xvg" /></template>
