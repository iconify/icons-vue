<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp-oslbcg.css';
import '../../css/x/x1lrm4okj.css';
import '../../css/w/waeaixbmn.css';
import '../../css/i/ifw1webqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-oslbcg"/><path class="x1lrm4okj"/><path class="waeaixbmn"/><path class="ifw1webqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mask-sad-bold-duotone" /></template>
