<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0im_gbxt.css';
import '../../css/t/t1ca65brz.css';
import '../../css/t/tw6980btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v0im_gbxt"/><path class="t1ca65brz"/><path class="tw6980btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapchat" /></template>
