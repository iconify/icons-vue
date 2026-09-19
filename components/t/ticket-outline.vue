<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pfvmrrbrb.css';
import '../../css/f/fnh1hbb7b.css';
import '../../css/f/f1ot_mbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ticket-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="pfvmrrbrb"/><path clip-rule="evenodd" class="fnh1hbb7b"/><path class="f1ot_mbyf"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:ticket-outline" /></template>
