<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia9w32xvn.css';
import '../../css/h/hoycbqb2w.css';
import '../../css/i/if9dnrb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ia9w32xvn"/><path class="hoycbqb2w"/><path class="if9dnrb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:windmill-48" /></template>
