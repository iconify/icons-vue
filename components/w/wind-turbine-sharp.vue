<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1h8neb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1h8neb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wind-turbine-sharp" /></template>
