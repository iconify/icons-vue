<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgry-2mds.css';
import '../../css/m/m4hhobcxn.css';
import '../../css/c/cx7t3xbre.css';
import '../../css/z/zqrfyfbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bgry-2mds"/><path class="m4hhobcxn"/><path class="cx7t3xbre"/><path class="zqrfyfbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pairdrop" /></template>
