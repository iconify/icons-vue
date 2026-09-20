<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw11znqtx.css';
import '../../css/w/wmpwcbcvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xw11znqtx"/><path class="wmpwcbcvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:marker-solid" /></template>
