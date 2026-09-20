<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqay7ob1p.css';
import '../../css/r/rs_g1igkr.css';
import '../../css/h/hkaof2wbu.css';
import '../../css/b/b457pmy8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kqay7ob1p"/><path class="rs_g1igkr"/><path class="hkaof2wbu"/><path class="b457pmy8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:wrench" /></template>
