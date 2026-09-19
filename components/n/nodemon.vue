<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euo4mnb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":451,"height":512};
const content = `<path class="euo4mnb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nodemon" /></template>
