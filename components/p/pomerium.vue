<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxys7u5-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxys7u5-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pomerium" /></template>
