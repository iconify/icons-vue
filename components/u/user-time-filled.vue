<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg3nfg2gw.css';
import '../../css/z/zhypwob1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg3nfg2gw"/><path class="zhypwob1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-time-filled" /></template>
