<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5pil4b6d.css';
import '../../css/v/v5wzyp5ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5pil4b6d"/><circle class="v5wzyp5ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:view-alt-duotone" /></template>
