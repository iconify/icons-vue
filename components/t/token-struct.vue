<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spfghmjsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="spfghmjsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-struct" /></template>
