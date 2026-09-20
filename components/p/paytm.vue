<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dky1fac6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dky1fac6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:paytm" /></template>
