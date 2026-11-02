<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btcvrsb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btcvrsb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wave-hand-fill" /></template>
