<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk150c_4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nk150c_4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:shield" /></template>
