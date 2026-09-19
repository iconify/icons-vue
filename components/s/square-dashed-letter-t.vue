<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r60j53b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r60j53b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-dashed-letter-t" /></template>
