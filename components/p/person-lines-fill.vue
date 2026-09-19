<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfj87j4sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gfj87j4sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-lines-fill" /></template>
