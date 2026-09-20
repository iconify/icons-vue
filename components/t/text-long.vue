<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bajryhb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bajryhb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:text-long" /></template>
