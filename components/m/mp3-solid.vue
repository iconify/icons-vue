<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uql2cd25u.css';
import '../../css/l/l2fsr4bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uql2cd25u"/><path clip-rule="evenodd" class="l2fsr4bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mp3-solid" /></template>
