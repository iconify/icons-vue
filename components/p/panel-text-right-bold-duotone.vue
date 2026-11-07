<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1nbikbny.css';
import '../../css/l/lq958rfxi.css';
import '../../css/y/yy5pkcb2v.css';
import '../../css/v/vhokyxbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1nbikbny"/><path class="lq958rfxi"/><path class="yy5pkcb2v"/><path class="vhokyxbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-text-right-bold-duotone" /></template>
