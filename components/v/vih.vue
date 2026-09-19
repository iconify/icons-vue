<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to2lt32jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="to2lt32jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:vih" /></template>
