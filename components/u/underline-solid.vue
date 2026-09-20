<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9705yb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="m9705yb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:underline-solid" /></template>
