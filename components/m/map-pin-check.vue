<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv-fx5pmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv-fx5pmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-check" /></template>
