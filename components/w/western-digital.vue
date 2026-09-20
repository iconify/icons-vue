<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kszoi5bnf.css';
import '../../css/v/vt74m5b-v.css';
import '../../css/j/jmbmabbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kszoi5bnf"/><path class="vt74m5b-v"/><path class="jmbmabbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:western-digital" /></template>
