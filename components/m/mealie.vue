<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm_90bcmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm_90bcmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mealie" /></template>
