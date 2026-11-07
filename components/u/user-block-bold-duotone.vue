<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liywby_bb.css';
import '../../css/l/lc21qzuqt.css';
import '../../css/s/swt82ccqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="liywby_bb"/><path class="lc21qzuqt"/><path class="swt82ccqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-block-bold-duotone" /></template>
