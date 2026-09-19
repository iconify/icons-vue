<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn-nnpqzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn-nnpqzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:phone" /></template>
