<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlo573dxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlo573dxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:weblate" /></template>
