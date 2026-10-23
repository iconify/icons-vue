<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf-j6_d6b.css';
import '../../css/u/uzsvwtbuf.css';
import '../../css/u/uxrmrdb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf-j6_d6b"/><path class="uzsvwtbuf"/><path class="uxrmrdb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wifi-lock-filled" /></template>
