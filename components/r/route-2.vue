<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbtk0uc7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbtk0uc7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:route-2" /></template>
