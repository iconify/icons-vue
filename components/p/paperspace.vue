<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmiuys6ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmiuys6ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:paperspace" /></template>
