<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs782kb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs782kb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mug-heart" /></template>
