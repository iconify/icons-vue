<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dak6y7b8m.css';
import '../../css/z/zjptowt2p.css';
import '../../css/r/rtotpcckl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dak6y7b8m"/><path clip-rule="evenodd" class="zjptowt2p"/><path clip-rule="evenodd" class="rtotpcckl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:qr-code-duotone" /></template>
