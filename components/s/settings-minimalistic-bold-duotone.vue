<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woc-gln8b.css';
import '../../css/x/xh_rgzqbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="woc-gln8b"/><path class="xh_rgzqbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:settings-minimalistic-bold-duotone" /></template>
