<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh6129ykk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh6129ykk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:podcast-star" /></template>
