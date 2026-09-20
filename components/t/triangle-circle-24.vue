<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib9o-eblw.css';
import '../../css/k/kret6cc4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib9o-eblw"/><path class="kret6cc4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-circle-24" /></template>
