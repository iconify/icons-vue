<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx0pw3fls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gx0pw3fls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:table-cells-merge-solid" /></template>
