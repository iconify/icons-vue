<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k413-ia3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":512};
const content = `<path class="k413-ia3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:piggy-bank-coins" /></template>
