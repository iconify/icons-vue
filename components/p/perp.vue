<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds7fe3bxn.css';
import '../../css/s/svj3x-59u.css';
import '../../css/p/p5evhgbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ds7fe3bxn"/><path clip-rule="evenodd" class="svj3x-59u"/><path class="p5evhgbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:perp" /></template>
