<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa6-ti_2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aa6-ti_2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:save-as" /></template>
