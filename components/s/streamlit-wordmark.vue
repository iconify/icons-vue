<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7q0ht_hy.css';
import '../../css/d/dvn4mnkrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q7q0ht_hy"/><path class="dvn4mnkrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:streamlit-wordmark" /></template>
