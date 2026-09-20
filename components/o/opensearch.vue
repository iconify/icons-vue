<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bll1o-bzb.css';
import '../../css/v/v-kzk1h6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bll1o-bzb"/><path class="v-kzk1h6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensearch" /></template>
