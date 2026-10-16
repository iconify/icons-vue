<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn_rhpmlt.css';
import '../../css/i/inx0u8fpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bn_rhpmlt"/><path class="inx0u8fpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:siren-20" /></template>
