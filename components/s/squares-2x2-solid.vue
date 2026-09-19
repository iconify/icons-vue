<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvkjf9-0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvkjf9-0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:squares-2x2-solid" /></template>
