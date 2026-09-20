<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gem936ssu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gem936ssu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microsoftoutlook" /></template>
