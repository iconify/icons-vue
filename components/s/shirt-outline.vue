<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exs91hbwo.css';
import '../../css/k/kxpsf4byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="exs91hbwo"/><path class="kxpsf4byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:shirt-outline" /></template>
