<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpidcbbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="kpidcbbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:ror" /></template>
