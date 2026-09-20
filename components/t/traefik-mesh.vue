<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sor50jj-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sor50jj-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:traefik-mesh" /></template>
