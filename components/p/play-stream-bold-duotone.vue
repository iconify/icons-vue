<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_07ktnny.css';
import '../../css/j/jf0u8bbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o_07ktnny"/><path class="jf0u8bbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-stream-bold-duotone" /></template>
