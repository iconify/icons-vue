<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwne-p_1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lwne-p_1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-brackets" /></template>
