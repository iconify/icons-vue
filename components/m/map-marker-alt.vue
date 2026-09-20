<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuu8vi88c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuu8vi88c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:map-marker-alt" /></template>
