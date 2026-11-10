<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8r_ro_4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8r_ro_4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:newapi" /></template>
