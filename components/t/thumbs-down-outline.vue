<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfv8uccdl.css';
import '../../css/g/gr-hcbcva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfv8uccdl"/><path class="gr-hcbcva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:thumbs-down-outline" /></template>
