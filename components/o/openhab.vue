<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba7qtw72c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba7qtw72c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openhab" /></template>
