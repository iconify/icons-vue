<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqergccha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqergccha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:spotify" /></template>
