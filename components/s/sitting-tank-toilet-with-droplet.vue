<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buq6-w4ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="buq6-w4ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sitting-tank-toilet-with-droplet" /></template>
