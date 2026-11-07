<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn528ebyy.css';
import '../../css/i/ixa_i_r1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn528ebyy"/><path class="ixa_i_r1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-forward-outline" /></template>
