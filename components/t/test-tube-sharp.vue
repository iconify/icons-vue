<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxcqmib8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxcqmib8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube-sharp" /></template>
