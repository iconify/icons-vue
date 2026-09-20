<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w45-95bra.css';
import '../../css/s/s6vetcb2r.css';
import '../../css/s/sd2ql6hrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w45-95bra"/><path clip-rule="evenodd" class="s6vetcb2r"/><path class="sd2ql6hrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:umami" /></template>
