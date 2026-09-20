<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaugi6cfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uaugi6cfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:right-small-solid" /></template>
