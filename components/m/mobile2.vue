<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9xu63h9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s9xu63h9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:mobile2" /></template>
