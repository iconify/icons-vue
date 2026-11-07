<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjgo2gh2x.css';
import '../../css/g/g8oi6pbgw.css';
import '../../css/b/bpg1mxbva.css';
import '../../css/f/f123j2cib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cjgo2gh2x"/><path class="g8oi6pbgw"/><path class="bpg1mxbva"/><path clip-rule="evenodd" class="f123j2cib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-2-bold" /></template>
