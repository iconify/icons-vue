<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz4hxtbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz4hxtbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-5" /></template>
