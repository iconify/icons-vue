<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo0ilnblt.css';
import '../../css/p/pdeg3lb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo0ilnblt"/><path class="pdeg3lb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:stargaze" /></template>
