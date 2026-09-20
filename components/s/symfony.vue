<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6b9flb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6b9flb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:symfony" /></template>
