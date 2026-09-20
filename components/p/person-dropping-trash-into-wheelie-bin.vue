<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnq5ckf1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bnq5ckf1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-dropping-trash-into-wheelie-bin" /></template>
