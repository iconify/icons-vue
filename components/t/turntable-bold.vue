<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xibju_bku.css';
import '../../css/j/jstpxmb3e.css';
import '../../css/p/pkujej5gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xibju_bku"/><path class="jstpxmb3e"/><path clip-rule="evenodd" class="pkujej5gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-bold" /></template>
