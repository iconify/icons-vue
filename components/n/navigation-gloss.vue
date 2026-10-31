<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcxxlnbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcxxlnbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:navigation-gloss" /></template>
