<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtj-mrbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xtj-mrbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rack-ipc" /></template>
