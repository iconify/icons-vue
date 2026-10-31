<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dshwgkb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dshwgkb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubuntu" /></template>
