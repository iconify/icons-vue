<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yadkeksry.css';
import '../../css/g/gv5s0h4bv.css';
import '../../css/i/i-h5fzmsn.css';
import '../../css/w/wf_6ujbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yadkeksry"/><path clip-rule="evenodd" class="gv5s0h4bv"/><path class="i-h5fzmsn"/><path class="wf_6ujbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sale-outline" /></template>
