<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/josx51y5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="josx51y5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:yarn-16" /></template>
