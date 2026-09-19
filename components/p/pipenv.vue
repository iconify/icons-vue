<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu4wc-bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pu4wc-bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pipenv" /></template>
