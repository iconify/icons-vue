<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi_jt4bbp.css';
import '../../css/y/ykelgknbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wi_jt4bbp"/><path class="ykelgknbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-left-bold" /></template>
