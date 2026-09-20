<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1az0cgxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l1az0cgxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yugabytedb-dark" /></template>
