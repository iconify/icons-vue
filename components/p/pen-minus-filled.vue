<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lasjdldku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lasjdldku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pen-minus-filled" /></template>
