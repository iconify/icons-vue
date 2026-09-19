<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emjhn05hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="emjhn05hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-dashed-letter-a" /></template>
