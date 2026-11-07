<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glv5hj-md.css';
import '../../css/d/d3no_4bwo.css';
import '../../css/c/ctpju6bji.css';
import '../../css/j/jjk_8ebes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glv5hj-md"/><path clip-rule="evenodd" class="d3no_4bwo"/><path class="ctpju6bji"/><path class="jjk_8ebes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-smile-square-bold-duotone" /></template>
