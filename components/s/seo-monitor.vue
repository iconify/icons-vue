<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7o7o5b7l.css';
import '../../css/t/t6gh8ibmm.css';
import '../../css/s/sehm2dsik.css';
import '../../css/q/qu6l8ybxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="o7o7o5b7l"/><path clip-rule="evenodd" class="t6gh8ibmm"/><path class="sehm2dsik"/><path clip-rule="evenodd" class="qu6l8ybxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:seo-monitor" /></template>
