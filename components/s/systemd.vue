<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3g7qk_6v.css';
import '../../css/q/q9xt_ac5x.css';
import '../../css/r/rj_fo2b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z3g7qk_6v"/><circle class="q9xt_ac5x"/><path class="rj_fo2b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:systemd" /></template>
