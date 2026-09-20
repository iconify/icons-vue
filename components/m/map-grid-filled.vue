<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opos94p9c.css';
import '../../css/o/o42lp8b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opos94p9c"/><path class="o42lp8b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-grid-filled" /></template>
