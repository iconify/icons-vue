<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxu1rfbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xxu1rfbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:vim-solid" /></template>
