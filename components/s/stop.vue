<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvoo8fzsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvoo8fzsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:stop" /></template>
