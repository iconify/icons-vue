<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkhl62fff.css';
import '../../css/j/jftj_8bfk.css';
import '../../css/e/elc-1sb2u.css';
import '../../css/d/dq5_8vb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkhl62fff"/><path class="jftj_8bfk"/><path class="elc-1sb2u"/><path clip-rule="evenodd" class="dq5_8vb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ufo-2-outline" /></template>
