<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_28jmb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k_28jmb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:nut-hex" /></template>
