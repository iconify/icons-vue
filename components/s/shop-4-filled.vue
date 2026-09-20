<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok2n7cp7w.css';
import '../../css/w/wus1oo58n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok2n7cp7w"/><path class="wus1oo58n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:shop-4-filled" /></template>
