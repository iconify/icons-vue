<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnku-pbna.css';
import '../../css/s/sqo3g6whm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnku-pbna"/><path class="sqo3g6whm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:siri-fill" /></template>
