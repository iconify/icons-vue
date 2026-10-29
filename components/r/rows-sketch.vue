<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bbe_xybxr.css';
import '../../css/k/kizbw6bue.css';
import '../../css/j/jifcohbtm.css';
import '../../css/h/h5utuuptd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bbe_xybxr"/><path class="kizbw6bue wm-a"/><path class="jifcohbtm wm-k"/><path class="h5utuuptd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rows-sketch" /></template>
