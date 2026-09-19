<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_pu1q0jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="i_pu1q0jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:unfold-horizontal-outline" /></template>
