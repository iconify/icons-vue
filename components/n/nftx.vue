<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyjy3kbll.css';
import '../../css/p/p_067m8_e.css';
import '../../css/v/va1a_7b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyjy3kbll"/><path class="p_067m8_e"/><path class="va1a_7b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nftx" /></template>
