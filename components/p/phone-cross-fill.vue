<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxsznzm1o.css';
import '../../css/r/r20wh5g3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxsznzm1o"/><path class="r20wh5g3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-cross-fill" /></template>
