<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk_28bbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk_28bbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-minus-2" /></template>
