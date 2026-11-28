<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc2wt0bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc2wt0bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:package-refresh" /></template>
