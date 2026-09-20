<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e29om5blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e29om5blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-using-mounted-binoculars" /></template>
