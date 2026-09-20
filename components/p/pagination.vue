<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk0u-ybaf.css';
import '../../css/x/xekl2mwvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="pk0u-ybaf"/><path class="xekl2mwvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pagination" /></template>
