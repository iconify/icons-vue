<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aah1accvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aah1accvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:react" /></template>
