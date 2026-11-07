<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iwt0w8b9p.css';
import '../../css/p/pbchzzbqf.css';
import '../../css/h/hcke0zwib.css';
import '../../css/p/p2spj-b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iwt0w8b9p"/><path class="pbchzzbqf"/><path class="hcke0zwib"/><path class="p2spj-b_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-full-screen-broken" /></template>
