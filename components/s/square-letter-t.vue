<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jimqm7bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jimqm7bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-letter-t" /></template>
