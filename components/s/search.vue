<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs7gssbtl.css';
import '../../css/s/s1qbw8bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="hs7gssbtl"/><path class="s1qbw8bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:search" /></template>
