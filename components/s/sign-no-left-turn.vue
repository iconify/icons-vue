<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5le-hcvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x5le-hcvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sign-no-left-turn" /></template>
