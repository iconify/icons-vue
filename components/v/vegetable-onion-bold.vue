<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2bvsbcom.css';
import '../../css/l/l7cx49rxz.css';
import '../../css/d/dif39_b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2bvsbcom"/><path class="l7cx49rxz"/><path class="dif39_b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:vegetable-onion-bold" /></template>
