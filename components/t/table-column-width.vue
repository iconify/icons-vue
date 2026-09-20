<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqd23qb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqd23qb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-column-width" /></template>
