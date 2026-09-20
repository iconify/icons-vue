<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m9y9kqbko.css';
import '../../css/b/bn0slib0i.css';
import '../../css/s/spkxylb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m9y9kqbko"/><path class="bn0slib0i"/><path class="spkxylb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-rings-line-duotone" /></template>
