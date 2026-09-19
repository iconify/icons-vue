<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gndumxe4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":832};
const content = `<path class="gndumxe4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:saurus" /></template>
