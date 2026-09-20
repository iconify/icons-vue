<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqw6wkb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqw6wkb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:root" /></template>
