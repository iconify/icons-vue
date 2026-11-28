<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu_3zfgud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu_3zfgud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:salt-shaker" /></template>
