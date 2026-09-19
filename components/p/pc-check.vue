<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/acx96kbqj.css';
import '../../css/v/v5fixrg-m.css';
import '../../css/s/sm1bh3rcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="acx96kbqj"/><path class="v5fixrg-m"/><path class="sm1bh3rcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pc-check" /></template>
