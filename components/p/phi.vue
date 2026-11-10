<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htib2p0us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htib2p0us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:phi" /></template>
