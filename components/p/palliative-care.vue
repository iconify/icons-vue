<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4r6l7h7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y4r6l7h7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:palliative-care" /></template>
