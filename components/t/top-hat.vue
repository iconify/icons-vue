<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi7m7db4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mi7m7db4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:top-hat" /></template>
