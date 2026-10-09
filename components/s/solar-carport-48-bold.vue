<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u37j8eblv.css';
import '../../css/b/bj00cy14m.css';
import '../../css/h/hmvn1yvxd.css';
import '../../css/z/zkrdz4b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u37j8eblv"/><path class="bj00cy14m"/><path class="hmvn1yvxd"/><path class="zkrdz4b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-carport-48-bold" /></template>
