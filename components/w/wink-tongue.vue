<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl03k-beh.css';
import '../../css/a/aog7vpb_z.css';
import '../../css/a/an0_1xo_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl03k-beh"/><path class="aog7vpb_z"/><circle class="an0_1xo_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:wink-tongue" /></template>
