<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm3j0cc2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cm3j0cc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wger-dark" /></template>
