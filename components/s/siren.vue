<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw6_klbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw6_klbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:siren" /></template>
