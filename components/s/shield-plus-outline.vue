<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw53yobjk.css';
import '../../css/q/qwjuf14gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw53yobjk"/><path clip-rule="evenodd" class="qwjuf14gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-plus-outline" /></template>
