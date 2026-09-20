<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cro202h0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cro202h0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:srgssr" /></template>
