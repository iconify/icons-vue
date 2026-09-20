<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfv3ot-fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nfv3ot-fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:requirements" /></template>
