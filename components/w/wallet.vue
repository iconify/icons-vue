<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_txeacgn.css';
import '../../css/s/sn58b5b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_txeacgn"/><path class="sn58b5b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:wallet" /></template>
