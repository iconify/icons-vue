<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2c4dccfz.css';
import '../../css/r/rm7ga8nok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2c4dccfz"/><path class="rm7ga8nok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-3-bold" /></template>
