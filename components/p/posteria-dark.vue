<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8bdnmttq.css';
import '../../css/v/v_shcmxcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8bdnmttq"/><path class="v_shcmxcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posteria-dark" /></template>
