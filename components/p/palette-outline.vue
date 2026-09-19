<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vniww6bxz.css';
import '../../css/q/qtu4m29vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vniww6bxz"/><path clip-rule="evenodd" class="qtu4m29vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:palette-outline" /></template>
