<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg9et_bct.css';
import '../../css/j/j9xiqe_ui.css';
import '../../css/z/zyroygmzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rg9et_bct"/><path class="j9xiqe_ui"/><path class="zyroygmzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:tongue" /></template>
