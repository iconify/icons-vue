<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auw7t_nln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auw7t_nln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tnt" /></template>
