<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo1fbbcra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lo1fbbcra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:newrelic" /></template>
