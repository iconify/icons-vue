<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzbz9xb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzbz9xb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tet-plus" /></template>
