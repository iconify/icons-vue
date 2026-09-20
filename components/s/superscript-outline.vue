<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcn5xpbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tcn5xpbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:superscript-outline" /></template>
