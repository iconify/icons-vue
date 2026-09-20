<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx4hw-btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kx4hw-btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:svg-solid" /></template>
