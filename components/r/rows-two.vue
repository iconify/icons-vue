<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbb_oabdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbb_oabdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:rows-two" /></template>
