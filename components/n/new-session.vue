<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puc5bd2pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="puc5bd2pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:new-session" /></template>
