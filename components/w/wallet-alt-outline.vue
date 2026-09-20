<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_bs3g73h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m_bs3g73h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wallet-alt-outline" /></template>
