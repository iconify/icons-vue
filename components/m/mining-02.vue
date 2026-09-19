<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2x0wbcne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2x0wbcne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mining-02" /></template>
