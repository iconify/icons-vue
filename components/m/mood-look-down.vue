<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uubdgd69a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uubdgd69a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-look-down" /></template>
