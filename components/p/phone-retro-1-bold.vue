<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plcuanbng.css';
import '../../css/j/jx0lkpbqx.css';
import '../../css/a/a4nu-p1co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plcuanbng"/><path class="jx0lkpbqx"/><path class="a4nu-p1co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:phone-retro-1-bold" /></template>
