<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9ab1942s.css';
import '../../css/p/ptd7g-bjn.css';
import '../../css/a/ak2xe3bmn.css';
import '../../css/q/qwlxa1blq.css';
import '../../css/e/emoy-abso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d9ab1942s"/><path clip-rule="evenodd" class="ptd7g-bjn"/><path clip-rule="evenodd" class="ak2xe3bmn"/><path clip-rule="evenodd" class="qwlxa1blq"/><path class="emoy-abso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:touch-id-fingerprint-lock-1" /></template>
