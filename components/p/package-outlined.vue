<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxbvi_4ka.css';
import '../../css/z/z2pque0vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxbvi_4ka"/><path class="z2pque0vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:package-outlined" /></template>
