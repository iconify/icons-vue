<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f3v4tybxo.css';
import '../../css/w/w3m_3tb8c.css';
import '../../css/a/ajuvr4bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f3v4tybxo"/><path class="w3m_3tb8c"/><path class="ajuvr4bok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-unlock-01" /></template>
