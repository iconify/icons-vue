<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icnj0w2vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icnj0w2vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:single-woman" /></template>
