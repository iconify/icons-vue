<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baoz4od4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="baoz4od4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sizzle" /></template>
