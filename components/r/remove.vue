<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u20q-_bqv.css';
import '../../css/h/hmk826btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u20q-_bqv"/><path class="hmk826btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:remove" /></template>
