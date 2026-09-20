<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwzg04bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pwzg04bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wheelie-bin-and-bag-of-trash" /></template>
