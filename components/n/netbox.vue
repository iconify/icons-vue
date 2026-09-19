<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4z4o6b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s4z4o6b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:netbox" /></template>
