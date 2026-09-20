<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2i4q55vh.css';
import '../../css/f/frpv_vbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2i4q55vh"/><path class="frpv_vbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sort-amount-down" /></template>
