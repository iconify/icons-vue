<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jytnoj_6w.css';
import '../../css/y/yeai0_c-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jytnoj_6w"/><path class="yeai0_c-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:volume-up-fill" /></template>
