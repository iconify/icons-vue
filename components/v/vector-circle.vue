<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpjn_4b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kpjn_4b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:vector-circle" /></template>
