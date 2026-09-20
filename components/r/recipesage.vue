<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-0j0rbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y-0j0rbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:recipesage" /></template>
