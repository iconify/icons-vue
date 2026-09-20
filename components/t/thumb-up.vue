<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6dc8yq4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v6dc8yq4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:thumb-up" /></template>
