<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7lzhdc8k.css';
import '../../css/x/xg4x14bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7lzhdc8k"/><path class="xg4x14bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:multiply" /></template>
