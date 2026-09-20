<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwhd7bbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwhd7bbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pdq" /></template>
