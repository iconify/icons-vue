<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgyn-qbco.css';
import '../../css/i/i700k7_wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgyn-qbco"/><path clip-rule="evenodd" class="i700k7_wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nabox" /></template>
