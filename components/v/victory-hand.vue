<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enhazwbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="enhazwbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:victory-hand" /></template>
