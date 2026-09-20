<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b87r37bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b87r37bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zillow" /></template>
