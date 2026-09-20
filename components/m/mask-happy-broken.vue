<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ibwtqmhuq.css';
import '../../css/n/nxyeq8w_t.css';
import '../../css/r/r4ng58brp.css';
import '../../css/s/s6e9m8adu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ibwtqmhuq"/><path class="nxyeq8w_t"/><path class="r4ng58brp"/><path class="s6e9m8adu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mask-happy-broken" /></template>
