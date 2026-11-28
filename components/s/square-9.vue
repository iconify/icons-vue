<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj-fcgjrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj-fcgjrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-9" /></template>
