<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vla37tbfm.css';
import '../../css/t/t576d3m0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vla37tbfm"/><path class="t576d3m0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:question-duotone" /></template>
