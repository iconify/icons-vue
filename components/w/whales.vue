<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezrac2bcq.css';
import '../../css/c/cuj_81b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezrac2bcq"/><path class="cuj_81b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:whales" /></template>
