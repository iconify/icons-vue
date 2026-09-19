<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7kfgg1tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7kfgg1tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-vertical-light" /></template>
