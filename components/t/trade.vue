<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf04vdtkp.css';
import '../../css/y/yxe08ybje.css';
import '../../css/q/q1bn-vbpz.css';
import '../../css/a/a6c4neb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf04vdtkp"/><path class="yxe08ybje"/><path clip-rule="evenodd" class="q1bn-vbpz"/><path class="a6c4neb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:trade" /></template>
