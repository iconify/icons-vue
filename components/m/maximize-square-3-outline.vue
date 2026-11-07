<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhh-lmb1b.css';
import '../../css/w/wioqj5bua.css';
import '../../css/r/ru5wvccub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhh-lmb1b"/><path class="wioqj5bua"/><path clip-rule="evenodd" class="ru5wvccub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-3-outline" /></template>
