<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ral5x2b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="ral5x2b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:meh-blank" /></template>
