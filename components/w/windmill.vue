<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flo9z28mp.css';
import '../../css/n/ntt7ilb9v.css';
import '../../css/k/kwk2estza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="flo9z28mp"/><path class="ntt7ilb9v"/><path class="kwk2estza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:windmill" /></template>
