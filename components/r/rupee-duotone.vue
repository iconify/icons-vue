<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buan6_edz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buan6_edz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:rupee-duotone" /></template>
