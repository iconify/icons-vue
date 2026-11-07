<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jctn5cbgl.css';
import '../../css/u/u87ezyb8f.css';
import '../../css/b/bnvy-8cvd.css';
import '../../css/m/ms0ci5but.css';
import '../../css/d/dynz7dbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jctn5cbgl"/><path class="u87ezyb8f"/><path class="bnvy-8cvd"/><path clip-rule="evenodd" class="ms0ci5but"/><path clip-rule="evenodd" class="dynz7dbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-2-bold" /></template>
