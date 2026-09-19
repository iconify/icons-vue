<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqg2i0b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="rqg2i0b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tv" /></template>
