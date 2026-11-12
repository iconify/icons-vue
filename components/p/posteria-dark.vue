<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1e8thrft.css';
import '../../css/v/v_shcmxcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1e8thrft"/><path class="v_shcmxcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posteria-dark" /></template>
