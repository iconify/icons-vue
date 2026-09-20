<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_2inacgz.css';
import '../../css/l/lcg60_b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_2inacgz"/><path class="lcg60_b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zil" /></template>
