<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n30b-7l1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="n30b-7l1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wan-solid" /></template>
