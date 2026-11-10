<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpjp_c7is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rpjp_c7is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:sauropod" /></template>
