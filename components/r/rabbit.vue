<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvzm9-bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvzm9-bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:rabbit" /></template>
