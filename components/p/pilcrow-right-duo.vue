<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5sle4ebl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ap3wsxbft.css';
import '../../css/m/m_kz9zbhm.css';
import '../../css/m/mb8uzum2p.css';
import '../../css/f/f69sknybc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5sle4ebl secondary"/><g class="dt0cm9dhy primary"><path class="ap3wsxbft"/><path class="m_kz9zbhm"/><path class="mb8uzum2p"/><path class="f69sknybc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pilcrow-right-duo" /></template>
