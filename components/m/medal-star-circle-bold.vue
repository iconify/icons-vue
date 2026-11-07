<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss1pzwrkh.css';
import '../../css/z/zn22gsbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ss1pzwrkh"/><path class="zn22gsbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-circle-bold" /></template>
