<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmv1at-2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmv1at-2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nox" /></template>
