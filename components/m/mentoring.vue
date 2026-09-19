<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kfcfzzxue.css';
import '../../css/d/dzlldxbzo.css';
import '../../css/z/zoixtkcpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kfcfzzxue"/><path class="dzlldxbzo"/><path class="zoixtkcpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mentoring" /></template>
