<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuo7dyblv.css';
import '../../css/l/l8542ybkm.css';
import '../../css/l/lc21qzuqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yuo7dyblv"/><path class="l8542ybkm"/><path class="lc21qzuqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-cross-rounded-bold" /></template>
