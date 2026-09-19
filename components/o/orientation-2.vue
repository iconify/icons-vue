<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7xfp2n_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f7xfp2n_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:orientation-2" /></template>
