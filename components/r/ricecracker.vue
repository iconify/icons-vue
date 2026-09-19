<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofhjkacrl.css';
import '../../css/g/g53_4wpqu.css';
import '../../css/b/b7ri4q8vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="ofhjkacrl"/><path class="g53_4wpqu"/><path class="b7ri4q8vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:ricecracker" /></template>
