<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdfi9mb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdfi9mb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:statamic" /></template>
