<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7c6kyeht.css';
import '../../css/k/kd63pacrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7c6kyeht"/><path class="kd63pacrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:telegram-alt" /></template>
