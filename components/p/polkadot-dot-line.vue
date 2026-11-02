<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6fzji7ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6fzji7ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:polkadot-dot-line" /></template>
