<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvwx6cb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="bvwx6cb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:maximum-temp-200-390" /></template>
