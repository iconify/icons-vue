<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tok2xfb_t.css';
import '../../css/c/cp5kib_ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tok2xfb_t"/><path class="cp5kib_ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-right-exit-filled" /></template>
