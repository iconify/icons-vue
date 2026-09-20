<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ona9t_b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ona9t_b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:plus-16" /></template>
