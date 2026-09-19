<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ah_3bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ah_3bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-left-03" /></template>
