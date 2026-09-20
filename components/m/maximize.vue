<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmii_abek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gmii_abek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:maximize" /></template>
