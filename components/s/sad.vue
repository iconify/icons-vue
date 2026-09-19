<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn2t-zwkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn2t-zwkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:sad" /></template>
