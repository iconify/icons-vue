<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef4civ4fj.css';
import '../../css/n/nbf3jcbto.css';
import '../../css/d/dj_zfb5pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef4civ4fj"/><path clip-rule="evenodd" class="nbf3jcbto"/><path clip-rule="evenodd" class="dj_zfb5pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:miner-filled" /></template>
