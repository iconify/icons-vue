<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3csk8btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3csk8btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:quote-single-end-sharp-fill" /></template>
