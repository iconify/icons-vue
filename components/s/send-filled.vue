<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/osuc4rb0v.css';
import '../../css/s/s_h1tmbej.css';
import '../../css/p/prd1nacfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="osuc4rb0v"/><path class="s_h1tmbej"/><path class="prd1nacfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:send-filled" /></template>
