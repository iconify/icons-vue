<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6yq8fyey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z6yq8fyey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-e-with-parking-meter" /></template>
